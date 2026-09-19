<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3ejxbqwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="v3ejxbqwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:percentage" {...props}></Icon>
