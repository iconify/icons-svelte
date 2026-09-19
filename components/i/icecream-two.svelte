<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/z/z2e5f5b3x.css';
import '../../css/e/e6ddg3v6m.css';
import '../../css/g/gysymsbqn.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGrPciNeMA"><g class="hv130ab-t"><path class="z2e5f5b3x"/><path class="e6ddg3v6m"/><path class="gysymsbqn"/></g></mask></defs><path mask="url(#SVGrPciNeMA)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:icecream-two" {...props}></Icon>
