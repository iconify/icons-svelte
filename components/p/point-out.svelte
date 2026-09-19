<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9y7s-r2s.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJzsKOqQJ"><path class="r9y7s-r2s"/></mask></defs><path mask="url(#SVGJzsKOqQJ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:point-out" {...props}></Icon>
