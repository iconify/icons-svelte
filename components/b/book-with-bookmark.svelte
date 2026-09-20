<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa4slwabl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xa4slwabl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:book-with-bookmark" {...props}></Icon>
