<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh5f3c7jr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="zh5f3c7jr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:percentage" {...props}></Icon>
