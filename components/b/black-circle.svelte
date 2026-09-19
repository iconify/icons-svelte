<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogeftcbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ogeftcbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:black-circle" {...props}></Icon>
