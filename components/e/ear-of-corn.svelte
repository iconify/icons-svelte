<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ace0o87kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ace0o87kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:ear-of-corn" {...props}></Icon>
