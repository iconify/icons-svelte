<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8g5vabnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d8g5vabnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:home-fill-16" {...props}></Icon>
