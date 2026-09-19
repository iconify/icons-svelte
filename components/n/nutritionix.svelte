<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvayc7r2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="bvayc7r2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:nutritionix" {...props}></Icon>
