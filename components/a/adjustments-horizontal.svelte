<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdh9iubqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fdh9iubqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:adjustments-horizontal" {...props}></Icon>
