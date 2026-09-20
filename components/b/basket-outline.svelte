<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u67prxy3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u67prxy3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:basket-outline" {...props}></Icon>
