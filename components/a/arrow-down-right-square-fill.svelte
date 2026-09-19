<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd34iubbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zd34iubbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-down-right-square-fill" {...props}></Icon>
