<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yih83mira.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGxYujDeIh"><path class="yih83mira"/></mask></defs><path mask="url(#SVGxYujDeIh)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:left-two" {...props}></Icon>
