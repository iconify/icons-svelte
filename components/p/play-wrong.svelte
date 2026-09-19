<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/a/afw5bxb9f.css';
import '../../css/s/s51uqybkz.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGu13uHDQK"><g class="v3_i3wktz"><path class="afw5bxb9f"/><path class="s51uqybkz"/></g></mask></defs><path mask="url(#SVGu13uHDQK)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:play-wrong" {...props}></Icon>
