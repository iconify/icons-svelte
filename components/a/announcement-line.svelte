<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-pj1xb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-pj1xb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:announcement-line" {...props}></Icon>
