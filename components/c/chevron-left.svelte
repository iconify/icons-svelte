<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx860hber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yx860hber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chevron-left" {...props}></Icon>
