<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/c/cu5xsb1ef.css';
import '../../css/p/pt26ck9bi.css';
import '../../css/c/cmx854b6j.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwRs5FcDi"><g class="hv130ab-t"><rect class="cu5xsb1ef"/><path class="pt26ck9bi"/><path class="cmx854b6j"/></g></mask></defs><path mask="url(#SVGwRs5FcDi)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:ethernet-off" {...props}></Icon>
