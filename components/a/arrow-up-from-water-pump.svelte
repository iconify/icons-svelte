<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_1dsscgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="p_1dsscgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:arrow-up-from-water-pump" {...props}></Icon>
