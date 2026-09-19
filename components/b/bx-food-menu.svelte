<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg1t8_b4v.css';
import '../../css/l/lr3x0vl_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg1t8_b4v"/><path class="lr3x0vl_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-food-menu" {...props}></Icon>
