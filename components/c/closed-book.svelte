<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4atj1bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a4atj1bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:closed-book" {...props}></Icon>
