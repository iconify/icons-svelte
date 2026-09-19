<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b74uycbvr.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG0J8iwcBH"><path class="b74uycbvr"/></mask></defs><path mask="url(#SVG0J8iwcBH)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:hi" {...props}></Icon>
