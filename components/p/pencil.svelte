<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1nfpfxmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="a1nfpfxmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:pencil" {...props}></Icon>
