<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt9p-ac4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kt9p-ac4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:delete-columns" {...props}></Icon>
