<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo_psbbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo_psbbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pixelfed-fill" {...props}></Icon>
