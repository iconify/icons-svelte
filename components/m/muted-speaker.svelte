<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg5ntsbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vg5ntsbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:muted-speaker" {...props}></Icon>
