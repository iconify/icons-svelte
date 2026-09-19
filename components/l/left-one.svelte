<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx7st-bid.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGDulKzedE"><path class="bx7st-bid"/></mask></defs><path mask="url(#SVGDulKzedE)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:left-one" {...props}></Icon>
