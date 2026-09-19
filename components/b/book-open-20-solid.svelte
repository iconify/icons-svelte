<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zksklzbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zksklzbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:book-open-20-solid" {...props}></Icon>
