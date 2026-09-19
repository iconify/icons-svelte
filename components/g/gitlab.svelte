<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j745orp_y.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtKIw9llJ"><path class="j745orp_y"/></mask></defs><path mask="url(#SVGtKIw9llJ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:gitlab" {...props}></Icon>
