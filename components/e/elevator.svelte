<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs0o44c0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fs0o44c0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:elevator" {...props}></Icon>
