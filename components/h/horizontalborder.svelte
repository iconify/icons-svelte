<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tor7uzoal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":960};
const content = `<path class="tor7uzoal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:horizontalborder" {...props}></Icon>
