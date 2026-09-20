<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aksvw8bwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aksvw8bwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:remove-format" {...props}></Icon>
