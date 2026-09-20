<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5wuqj8_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j5wuqj8_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:redo-solid" {...props}></Icon>
