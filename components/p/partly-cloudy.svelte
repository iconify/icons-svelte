<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7v3c9hfx.css';
import '../../css/j/jaeag7yzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h7v3c9hfx"/><path class="jaeag7yzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:partly-cloudy" {...props}></Icon>
