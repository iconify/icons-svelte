<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu06apb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xu06apb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:food-drinks-wine-glass-drink-cook-glass-cooking-wine-nutrition-food" {...props}></Icon>
