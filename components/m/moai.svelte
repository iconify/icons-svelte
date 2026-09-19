<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0c3afbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g0c3afbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:moai" {...props}></Icon>
