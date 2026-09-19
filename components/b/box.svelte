<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qppkd2b9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="qppkd2b9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:box" {...props}></Icon>
