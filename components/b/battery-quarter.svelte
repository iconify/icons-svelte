<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2qfjvb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="z2qfjvb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:battery-quarter" {...props}></Icon>
