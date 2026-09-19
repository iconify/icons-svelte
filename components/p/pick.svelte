<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osfx-_bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="osfx-_bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:pick" {...props}></Icon>
