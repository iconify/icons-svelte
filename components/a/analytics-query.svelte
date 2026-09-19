<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9hxeub5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="m9hxeub5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:analytics-query" {...props}></Icon>
