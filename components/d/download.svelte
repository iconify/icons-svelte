<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_zo3jt-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t_zo3jt-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:download" {...props}></Icon>
