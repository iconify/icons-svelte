<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u5rk34b7w.css';
import '../../css/y/yh4tz_b5v.css';
import '../../css/c/cfc90nvlc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u5rk34b7w"/><path class="yh4tz_b5v"/><path class="cfc90nvlc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:brick-wall-shield-duotone" {...props}></Icon>
