<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x853vnbqo.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGa6UUhcmp"><path class="x853vnbqo"/></mask></defs><path mask="url(#SVGa6UUhcmp)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:block-seven" {...props}></Icon>
