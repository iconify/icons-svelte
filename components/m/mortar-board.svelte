<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsdt2wbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bsdt2wbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:mortar-board" {...props}></Icon>
