<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/a/a6flzv85o.css';
import '../../css/s/sdaucgb_l.css';
import '../../css/h/hyoz_h2gb.css';
import '../../css/q/qr4ochb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="a6flzv85o wm-deco"/><path class="sdaucgb_l wm-deco"/><path class="hyoz_h2gb wm-k"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lightbulb-off-blueprint" {...props}></Icon>
