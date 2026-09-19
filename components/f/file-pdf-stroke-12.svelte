<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lou9a14vc.css';
import '../../css/j/j2bufmatg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lou9a14vc"/><rect class="j2bufmatg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-pdf-stroke-12" {...props}></Icon>
