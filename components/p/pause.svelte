<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oslqv1qoq.css';
import '../../css/i/i2ugv7h_j.css';
import '../../css/u/un0mksblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="oslqv1qoq"><rect class="i2ugv7h_j"/><rect class="un0mksblv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:pause" {...props}></Icon>
