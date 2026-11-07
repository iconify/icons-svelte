<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g65hvpbwb.css';
import '../../css/q/q_b498z9b.css';
import '../../css/c/cxf8pnbrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g65hvpbwb"/><path class="q_b498z9b"/><path class="cxf8pnbrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:moon-sleep-bold" {...props}></Icon>
