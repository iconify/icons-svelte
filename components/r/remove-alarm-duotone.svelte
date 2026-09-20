<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b0n8abcgf.css';
import '../../css/c/c37hiwe8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b0n8abcgf"/><path class="c37hiwe8x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:remove-alarm-duotone" {...props}></Icon>
