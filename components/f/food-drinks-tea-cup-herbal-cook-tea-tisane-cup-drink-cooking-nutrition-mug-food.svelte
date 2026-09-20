<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv0c3kbte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yv0c3kbte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:food-drinks-tea-cup-herbal-cook-tea-tisane-cup-drink-cooking-nutrition-mug-food" {...props}></Icon>
