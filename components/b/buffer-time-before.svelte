<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwyqtbq_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="uwyqtbq_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:buffer-time-before" {...props}></Icon>
