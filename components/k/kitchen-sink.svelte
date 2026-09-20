<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erj58-puz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="erj58-puz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:kitchen-sink" {...props}></Icon>
