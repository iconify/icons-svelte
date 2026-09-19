<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae8u1iful.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ae8u1iful"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:grin-stars" {...props}></Icon>
