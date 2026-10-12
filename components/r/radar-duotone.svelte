<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/ud9660a5y.css';
import '../../css/n/nx2zbfb5m.css';
import '../../css/n/nzmariesu.css';
import '../../css/n/nbqssjb9c.css';
import '../../css/s/s4cdm1nek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ud9660a5y"/><path class="nx2zbfb5m"/><path class="nzmariesu"/><path class="nbqssjb9c"/><path class="s4cdm1nek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:radar-duotone" {...props}></Icon>
