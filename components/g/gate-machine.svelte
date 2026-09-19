<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/k/ktk03iqiw.css';
import '../../css/y/y45tttcaa.css';
import '../../css/f/fk9nibbzj.css';
import '../../css/y/y0yq2e4to.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGsEOG5bsW"><g class="hv130ab-t"><path class="ktk03iqiw"/><path class="y45tttcaa"/><path class="fk9nibbzj"/><path class="y0yq2e4to"/></g></mask></defs><path mask="url(#SVGsEOG5bsW)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:gate-machine" {...props}></Icon>
