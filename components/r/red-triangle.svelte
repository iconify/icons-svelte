<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6-4pabmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r6-4pabmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:red-triangle" {...props}></Icon>
