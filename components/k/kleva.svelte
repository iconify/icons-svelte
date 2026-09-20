<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwjj_mb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwjj_mb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kleva" {...props}></Icon>
