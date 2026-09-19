<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9x9k5jqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b9x9k5jqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:fountain" {...props}></Icon>
