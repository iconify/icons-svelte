<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpz8nccen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wpz8nccen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:docktop" {...props}></Icon>
