<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6wgt-bjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="t6wgt-bjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pixijs" {...props}></Icon>
