<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5u0jjb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n5u0jjb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:puzzle-piece" {...props}></Icon>
