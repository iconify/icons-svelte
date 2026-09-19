<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/n/n5yjc01jy.css';
import '../../css/b/brmmwgb3i.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9N9LFbAv"><g class="hv130ab-t"><path class="n5yjc01jy"/><path class="brmmwgb3i"/></g></mask></defs><path mask="url(#SVG9N9LFbAv)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:bread" {...props}></Icon>
