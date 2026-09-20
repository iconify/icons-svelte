<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myapyabmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="myapyabmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:drink-food-fruit" {...props}></Icon>
