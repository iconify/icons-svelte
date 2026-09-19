<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-1r0llge.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGx6kK0d0v"><path class="w-1r0llge"/></mask></defs><path mask="url(#SVGx6kK0d0v)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:horizontal-tidy-up" {...props}></Icon>
