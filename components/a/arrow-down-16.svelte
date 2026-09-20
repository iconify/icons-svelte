<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1zy7qbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t1zy7qbpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:arrow-down-16" {...props}></Icon>
