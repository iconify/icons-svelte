<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4r9pjegb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y4r9pjegb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:restaurant-noodle" {...props}></Icon>
