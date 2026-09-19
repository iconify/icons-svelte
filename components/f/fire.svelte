<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdf4gyzkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="bdf4gyzkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:fire" {...props}></Icon>
