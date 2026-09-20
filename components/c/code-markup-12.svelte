<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kldnvggtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kldnvggtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:code-markup-12" {...props}></Icon>
