<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msau2_b3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="msau2_b3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:collection" {...props}></Icon>
