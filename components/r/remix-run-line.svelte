<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmobyc_fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmobyc_fv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:remix-run-line" {...props}></Icon>
