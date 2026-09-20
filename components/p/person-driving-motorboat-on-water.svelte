<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny9vn34ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ny9vn34ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-driving-motorboat-on-water" {...props}></Icon>
