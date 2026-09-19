<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6mkcxi9w.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9QFFpbBI"><path class="u6mkcxi9w"/></mask></defs><path mask="url(#SVG9QFFpbBI)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:good-two" {...props}></Icon>
