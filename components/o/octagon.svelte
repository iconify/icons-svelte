<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvl1ieach.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGSTYrZqfb"><path class="cvl1ieach"/></mask></defs><path mask="url(#SVGSTYrZqfb)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:octagon" {...props}></Icon>
