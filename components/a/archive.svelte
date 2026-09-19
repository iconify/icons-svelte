<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmhv16-fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zmhv16-fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:archive" {...props}></Icon>
