<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zibvcjlle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zibvcjlle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:life-preserver" {...props}></Icon>
