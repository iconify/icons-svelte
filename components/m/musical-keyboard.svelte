<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vld8rjbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vld8rjbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:musical-keyboard" {...props}></Icon>
