<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz2zpvbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iz2zpvbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:red-circle" {...props}></Icon>
