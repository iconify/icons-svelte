<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsijaab7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="bsijaab7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:food-drinks-cocktail-1-cook-alcohol-food-cocktail-drink-cooking-nutrition-alcoholic-beverage-glass" {...props}></Icon>
