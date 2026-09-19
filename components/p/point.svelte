<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4369xzyz.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdfUibcAN"><path class="u4369xzyz"/></mask></defs><path mask="url(#SVGdfUibcAN)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:point" {...props}></Icon>
