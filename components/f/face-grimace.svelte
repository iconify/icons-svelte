<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm9ypbioh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="sm9ypbioh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:face-grimace" {...props}></Icon>
