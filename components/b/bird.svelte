<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/isu9bqbpe.css';
import '../../css/x/xwe23ta8r.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGe3smqcPo"><g class="ft5dv1b6b"><path class="isu9bqbpe"/><circle class="xwe23ta8r"/></g></mask></defs><path mask="url(#SVGe3smqcPo)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:bird" {...props}></Icon>
