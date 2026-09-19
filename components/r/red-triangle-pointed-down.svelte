<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4dv_dq0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h4dv_dq0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:red-triangle-pointed-down" {...props}></Icon>
