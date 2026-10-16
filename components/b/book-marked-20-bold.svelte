<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al5fry1wp.css';
import '../../css/e/eremc1y7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="al5fry1wp"/><path class="eremc1y7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:book-marked-20-bold" {...props}></Icon>
