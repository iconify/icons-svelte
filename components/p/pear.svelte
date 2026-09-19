<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lke-3bb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lke-3bb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:pear" {...props}></Icon>
