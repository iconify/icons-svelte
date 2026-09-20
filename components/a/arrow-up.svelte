<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frjdkl5gg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="frjdkl5gg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:arrow-up" {...props}></Icon>
