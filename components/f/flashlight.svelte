<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9jv9jb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q9jv9jb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:flashlight" {...props}></Icon>
