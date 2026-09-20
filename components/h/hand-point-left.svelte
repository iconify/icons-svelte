<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9p9gqdyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g9p9gqdyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hand-point-left" {...props}></Icon>
