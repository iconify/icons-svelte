<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7jxwvbhs.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG1x4zrmde"><path class="x7jxwvbhs"/></mask></defs><path mask="url(#SVG1x4zrmde)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:moon" {...props}></Icon>
