<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1bue927j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c1bue927j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:happy-face-in-circle" {...props}></Icon>
