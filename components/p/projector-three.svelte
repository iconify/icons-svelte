<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/en76r3buf.css';
import '../../css/m/mh9t29bel.css';
import '../../css/k/klancfb5i.css';
import '../../css/t/t79-0v05c.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRHYZ4dmR"><g class="ft5dv1b6b"><path class="en76r3buf"/><path class="mh9t29bel"/><path class="klancfb5i"/><path class="t79-0v05c"/></g></mask></defs><path mask="url(#SVGRHYZ4dmR)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:projector-three" {...props}></Icon>
