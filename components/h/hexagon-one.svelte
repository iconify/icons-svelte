<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drn7cfb8z.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQsUaMe6L"><path class="drn7cfb8z"/></mask></defs><path mask="url(#SVGQsUaMe6L)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:hexagon-one" {...props}></Icon>
