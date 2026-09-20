<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwh5tq7ua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lwh5tq7ua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cam-disk" {...props}></Icon>
