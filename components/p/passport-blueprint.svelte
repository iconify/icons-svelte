<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/d/drg7l01fx.css';
import '../../css/s/sdaucgb_l.css';
import '../../css/m/mv85hfbyp.css';
import '../../css/f/fnudiubft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="drg7l01fx wm-deco"/><path class="sdaucgb_l wm-deco"/><path class="mv85hfbyp wm-k"/><path class="fnudiubft wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:passport-blueprint" {...props}></Icon>
