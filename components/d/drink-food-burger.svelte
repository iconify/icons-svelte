<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq8u6-brl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bq8u6-brl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:drink-food-burger" {...props}></Icon>
