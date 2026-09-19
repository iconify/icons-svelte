<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/w/w55in7b1i.css';
import '../../css/p/p7n68sf5k.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlxng2cfv"><g class="wwvp95byt"><path class="w55in7b1i"/><path class="p7n68sf5k"/></g></mask></defs><path mask="url(#SVGlxng2cfv)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:bytedance-mini-app" {...props}></Icon>
