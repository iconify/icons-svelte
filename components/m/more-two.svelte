<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x36h_kb1w.css';
import '../../css/p/p55tn28js.css';
import '../../css/o/o1ec32b0j.css';
import '../../css/v/v7m8vzxeb.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG3G7KoctU"><g class="ft5dv1b6b"><path class="x36h_kb1w"/><circle class="p55tn28js"/><circle class="o1ec32b0j"/><circle class="v7m8vzxeb"/></g></mask></defs><path mask="url(#SVG3G7KoctU)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:more-two" {...props}></Icon>
