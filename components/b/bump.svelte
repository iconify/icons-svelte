<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yivp0jbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yivp0jbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bump" {...props}></Icon>
