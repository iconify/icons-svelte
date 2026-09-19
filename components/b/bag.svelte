<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4f3d0b8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1025};
const content = `<path class="j4f3d0b8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bag" {...props}></Icon>
