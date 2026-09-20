<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhilkwbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uhilkwbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bench" {...props}></Icon>
