<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_jhyxxgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z_jhyxxgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:bathtub" {...props}></Icon>
