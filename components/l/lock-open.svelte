<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxqjs7aes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="wxqjs7aes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:lock-open" {...props}></Icon>
