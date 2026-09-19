<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/z/z2n1m4skg.css';
import '../../css/z/zjgmhkqxf.css';
import '../../css/x/xlw9t-4mj.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGsJ6YSwta"><g class="hv130ab-t"><path class="z2n1m4skg"/><circle class="zjgmhkqxf"/><path class="xlw9t-4mj"/></g></mask></defs><path mask="url(#SVGsJ6YSwta)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:radio-nanny" {...props}></Icon>
