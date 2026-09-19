<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6rpfejaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="p6rpfejaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:link-slash" {...props}></Icon>
