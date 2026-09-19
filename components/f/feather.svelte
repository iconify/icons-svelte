<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0r7ue6-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c0r7ue6-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:feather" {...props}></Icon>
