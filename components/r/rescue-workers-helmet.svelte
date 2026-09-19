<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_qonyqlp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h_qonyqlp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:rescue-workers-helmet" {...props}></Icon>
