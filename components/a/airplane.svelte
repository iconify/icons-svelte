<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yygam6b7j.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnnJ8QrkK"><path class="yygam6b7j"/></mask></defs><path mask="url(#SVGnnJ8QrkK)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:airplane" {...props}></Icon>
