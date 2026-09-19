<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvfujmbgg.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGFlF8Ac6N"><path class="xvfujmbgg"/></mask></defs><path mask="url(#SVGFlF8Ac6N)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:rectangle-small" {...props}></Icon>
