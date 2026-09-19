<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sts20cc0v.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG5oSYUcve"><path class="sts20cc0v"/></mask></defs><path mask="url(#SVG5oSYUcve)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:one" {...props}></Icon>
