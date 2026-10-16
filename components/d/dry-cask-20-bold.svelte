<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8tgbj8rv.css';
import '../../css/g/glfmzd9iy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f8tgbj8rv"/><path class="glfmzd9iy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dry-cask-20-bold" {...props}></Icon>
