<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co9wg_bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="co9wg_bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:book-bookmark" {...props}></Icon>
