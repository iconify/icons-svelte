<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o538qrz7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="o538qrz7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:grid-vertical" {...props}></Icon>
