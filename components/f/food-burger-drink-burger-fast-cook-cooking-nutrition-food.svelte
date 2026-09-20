<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyaawlnzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="gyaawlnzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:food-burger-drink-burger-fast-cook-cooking-nutrition-food" {...props}></Icon>
