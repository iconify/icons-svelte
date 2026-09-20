<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7pgfbc9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u7pgfbc9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:loop" {...props}></Icon>
