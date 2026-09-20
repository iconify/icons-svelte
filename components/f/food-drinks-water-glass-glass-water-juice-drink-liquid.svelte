<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae4o2u4po.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ae4o2u4po"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:food-drinks-water-glass-glass-water-juice-drink-liquid" {...props}></Icon>
