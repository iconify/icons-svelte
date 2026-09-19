<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuxbbqk4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vuxbbqk4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:align-justify-fill-16" {...props}></Icon>
