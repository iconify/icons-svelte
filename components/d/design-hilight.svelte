<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie3fup9fg.css';
import '../../css/l/lsattvb1c.css';
import '../../css/x/x6mcnkwhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ie3fup9fg"/><path class="lsattvb1c"/><path class="x6mcnkwhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:design-hilight" {...props}></Icon>
