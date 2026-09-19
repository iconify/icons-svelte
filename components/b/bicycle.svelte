<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk70g6bff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zk70g6bff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bicycle" {...props}></Icon>
