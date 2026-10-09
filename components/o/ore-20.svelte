<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d44p8wv5z.css';
import '../../css/t/tb4t4kb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d44p8wv5z"/><path class="tb4t4kb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ore-20" {...props}></Icon>
