<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbsp_yblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="kbsp_yblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:food-drinks-coffee-mug-coffee-cook-cup-drink-mug-cooking-nutrition-cafe-caffeine-food" {...props}></Icon>
