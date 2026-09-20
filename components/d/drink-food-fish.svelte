<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqh39ybdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cqh39ybdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:drink-food-fish" {...props}></Icon>
