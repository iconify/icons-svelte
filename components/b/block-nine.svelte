<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uijzg9bmt.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlxwUvcBQ"><path class="uijzg9bmt"/></mask></defs><path mask="url(#SVGlxwUvcBQ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:block-nine" {...props}></Icon>
