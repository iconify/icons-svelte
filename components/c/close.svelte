<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3fj106an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f3fj106an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:close" {...props}></Icon>
