<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qknx832so.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBYCIBewW"><path class="qknx832so"/></mask></defs><path mask="url(#SVGBYCIBewW)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:people" {...props}></Icon>
