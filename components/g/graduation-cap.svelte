<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhai6mw-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="yhai6mw-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:graduation-cap" {...props}></Icon>
