<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw8dj8x0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="aw8dj8x0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:plane-circle-check" {...props}></Icon>
