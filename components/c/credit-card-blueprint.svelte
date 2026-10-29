<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/k/k74zkac6c.css';
import '../../css/r/rhnsbwb-m.css';
import '../../css/t/tvbjsxrsv.css';
import '../../css/m/mikouibnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="k74zkac6c wm-deco"/><path class="rhnsbwb-m wm-deco"/><path class="tvbjsxrsv wm-k"/><path class="mikouibnu wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:credit-card-blueprint" {...props}></Icon>
