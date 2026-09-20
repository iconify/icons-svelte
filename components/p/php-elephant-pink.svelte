<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1ccb2w-q.css';
import '../../css/t/toaf3ebik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o1ccb2w-q"/><path class="toaf3ebik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:php-elephant-pink" {...props}></Icon>
