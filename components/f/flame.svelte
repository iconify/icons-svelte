<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-bjp6n_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="r-bjp6n_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:flame" {...props}></Icon>
