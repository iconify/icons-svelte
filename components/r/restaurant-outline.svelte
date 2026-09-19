<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2do7bc4s.css';
import '../../css/k/kue68edpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w2do7bc4s"/><path class="kue68edpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:restaurant-outline" {...props}></Icon>
