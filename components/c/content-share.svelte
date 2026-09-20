<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4mq2le0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q4mq2le0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-share" {...props}></Icon>
