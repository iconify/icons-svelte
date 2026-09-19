<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5f5q0zdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k5f5q0zdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:burger" {...props}></Icon>
