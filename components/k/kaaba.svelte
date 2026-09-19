<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5_99bc0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h5_99bc0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:kaaba" {...props}></Icon>
