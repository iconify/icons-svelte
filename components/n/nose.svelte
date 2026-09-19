<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u35ud5unf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u35ud5unf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:nose" {...props}></Icon>
