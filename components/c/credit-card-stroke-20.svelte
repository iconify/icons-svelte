<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhl4eccuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rhl4eccuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:credit-card-stroke-20" {...props}></Icon>
