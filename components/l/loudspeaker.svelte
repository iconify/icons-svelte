<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5hy1lvhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z5hy1lvhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:loudspeaker" {...props}></Icon>
