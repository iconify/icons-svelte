<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tcvle1blf.css';
import '../../css/n/n-xbr3p_n.css';
import '../../css/k/kymfg3bmi.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG6kMRMcjV"><g class="ft5dv1b6b"><rect class="tcvle1blf"/><path class="n-xbr3p_n"/><rect transform="rotate(90 15 29)" class="kymfg3bmi"/></g></mask></defs><path mask="url(#SVG6kMRMcjV)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:painted-screen" {...props}></Icon>
