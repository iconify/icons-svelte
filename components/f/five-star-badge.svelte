<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv9y21t5h.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGfoAOLxWE"><path class="kv9y21t5h"/></mask></defs><path mask="url(#SVGfoAOLxWE)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:five-star-badge" {...props}></Icon>
