<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/c/coe1g67pu.css';
import '../../css/w/w66q37m7c.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGjpVwVbCe"><g class="hv130ab-t"><path clip-rule="evenodd" class="coe1g67pu"/><path class="w66q37m7c"/></g></mask></defs><path mask="url(#SVGjpVwVbCe)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:drop-shadow-down" {...props}></Icon>
