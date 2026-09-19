<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adexpl72i.css';
import '../../css/k/kb9zbkb1z.css';
import '../../css/a/a7nlqfoyx.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGfrErJbUE"><g class="adexpl72i"><circle class="kb9zbkb1z"/><path class="a7nlqfoyx"/></g></mask></defs><path mask="url(#SVGfrErJbUE)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:red-cross" {...props}></Icon>
