<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq68h36xc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rq68h36xc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:corner-down-left-line" {...props}></Icon>
