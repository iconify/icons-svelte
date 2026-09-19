<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgix2db9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="sgix2db9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:arrows-down-to-people" {...props}></Icon>
