<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-bv_67hy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="e-bv_67hy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:pencil" {...props}></Icon>
