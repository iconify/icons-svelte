<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se5j6sb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="se5j6sb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:order-stratus" {...props}></Icon>
