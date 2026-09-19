<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz6m-e_na.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fz6m-e_na"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:glass-of-milk" {...props}></Icon>
