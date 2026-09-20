<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j61_c6bws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="j61_c6bws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:food-wheat-cook-plant-bread-gluten-grain-cooking-nutrition-food-wheat" {...props}></Icon>
