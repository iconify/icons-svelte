<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/a/agqn053tk.css';
import '../../css/f/flz8mqbuo.css';
import '../../css/u/uuef9bbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="agqn053tk"/><path class="flz8mqbuo"/><path class="uuef9bbcj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:captions-sparkles-sharp-two-tone" {...props}></Icon>
