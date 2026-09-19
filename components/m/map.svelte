<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1lv1ybfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j1lv1ybfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:map" {...props}></Icon>
