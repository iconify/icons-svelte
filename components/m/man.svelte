<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpx8-5bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tpx8-5bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:man" {...props}></Icon>
