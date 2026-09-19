<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjo4g5bry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jjo4g5bry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:fly" {...props}></Icon>
