<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-q1a4j0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s-q1a4j0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:inbox" {...props}></Icon>
