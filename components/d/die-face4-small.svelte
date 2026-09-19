<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0c8g-3wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="b0c8g-3wh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:die-face4-small" {...props}></Icon>
