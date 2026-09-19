<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4pf3kmmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w4pf3kmmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloud-rain-heavy-fill" {...props}></Icon>
