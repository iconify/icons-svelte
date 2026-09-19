<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg6u5vbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yg6u5vbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:lifehalf" {...props}></Icon>
