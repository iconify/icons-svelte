<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zufra-4nx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zufra-4nx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:cart-o" {...props}></Icon>
