<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoas7vbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zoas7vbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:book-with-balance-scales" {...props}></Icon>
