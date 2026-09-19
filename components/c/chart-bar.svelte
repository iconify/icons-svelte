<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c28q9nbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c28q9nbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:chart-bar" {...props}></Icon>
