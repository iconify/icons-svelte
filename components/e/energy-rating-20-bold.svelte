<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9l9ao62c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n9l9ao62c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-rating-20-bold" {...props}></Icon>
