<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slq6yjsci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="slq6yjsci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:food-kitchenware-no-food-allowed-fork-spoon-food-dine-cook-utensils-eat-restaurant-not-allowed" {...props}></Icon>
