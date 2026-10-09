<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia51n3hgg.css';
import '../../css/t/tv9ekks-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ia51n3hgg"/><path class="tv9ekks-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:laundry-basket-20-bold" {...props}></Icon>
