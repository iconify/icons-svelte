<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k17m1b2dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="k17m1b2dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:apple-whole" {...props}></Icon>
