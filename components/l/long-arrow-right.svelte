<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arjc7_bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="arjc7_bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:long-arrow-right" {...props}></Icon>
