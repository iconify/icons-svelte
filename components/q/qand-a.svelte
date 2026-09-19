<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svd0sybzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="svd0sybzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:qand-a" {...props}></Icon>
