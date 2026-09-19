<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yulthovvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yulthovvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:cloud-moon" {...props}></Icon>
