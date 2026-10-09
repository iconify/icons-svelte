<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwjx20d_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jwjx20d_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:navigation-off-20-bold" {...props}></Icon>
