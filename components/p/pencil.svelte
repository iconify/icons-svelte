<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhbi0hb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hhbi0hb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:pencil" {...props}></Icon>
