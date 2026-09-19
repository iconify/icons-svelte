<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wewar8boz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wewar8boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:job-daemon" {...props}></Icon>
