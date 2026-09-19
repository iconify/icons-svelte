<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef3ym8b9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":480};
const content = `<path class="ef3ym8b9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:group" {...props}></Icon>
