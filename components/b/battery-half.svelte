<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9ciw2bty.css';
import '../../css/l/lnzzmyg9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r9ciw2bty"/><path class="lnzzmyg9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:battery-half" {...props}></Icon>
