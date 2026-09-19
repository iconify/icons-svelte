<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/a/af7k0bcjr.css';
import '../../css/z/z4mkicczo.css';
import '../../css/g/gn-ngo33l.css';
import '../../css/m/myt3h8b6l.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGjWkfddWq"><g class="hv130ab-t"><path class="af7k0bcjr"/><path class="z4mkicczo"/><path class="gn-ngo33l"/><path class="myt3h8b6l"/></g></mask></defs><path mask="url(#SVGjWkfddWq)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:excel" {...props}></Icon>
