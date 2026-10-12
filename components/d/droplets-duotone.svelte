<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aprqnrbwu.css';
import '../../css/w/w0ez89ben.css';
import '../../css/r/refb60b5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="aprqnrbwu"/><path class="w0ez89ben"/><path class="refb60b5t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:droplets-duotone" {...props}></Icon>
