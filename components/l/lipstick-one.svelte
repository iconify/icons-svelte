<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adexpl72i.css';
import '../../css/c/cf52fycgx.css';
import '../../css/u/u5_5228jl.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGCnMsPcDo"><g class="adexpl72i"><path class="cf52fycgx"/><path class="u5_5228jl"/></g></mask></defs><path mask="url(#SVGCnMsPcDo)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:lipstick-one" {...props}></Icon>
