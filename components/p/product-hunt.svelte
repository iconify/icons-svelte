<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrn2e5z6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="zrn2e5z6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:product-hunt" {...props}></Icon>
