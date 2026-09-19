<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6y97_l8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y6y97_l8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:feather" {...props}></Icon>
