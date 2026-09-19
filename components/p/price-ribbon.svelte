<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-4dylbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w-4dylbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:price-ribbon" {...props}></Icon>
