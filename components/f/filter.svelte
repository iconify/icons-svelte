<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4wis2bvm.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGsu0PwdKx"><path class="x4wis2bvm"/></mask></defs><path mask="url(#SVGsu0PwdKx)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:filter" {...props}></Icon>
