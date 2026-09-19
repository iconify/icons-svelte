<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec97uj83u.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwTKYc5fj"><path class="ec97uj83u"/></mask></defs><path mask="url(#SVGwTKYc5fj)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:down-one" {...props}></Icon>
