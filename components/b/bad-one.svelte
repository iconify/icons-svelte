<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8x7susgg.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHtA3wd4c"><path class="d8x7susgg"/></mask></defs><path mask="url(#SVGHtA3wd4c)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:bad-one" {...props}></Icon>
