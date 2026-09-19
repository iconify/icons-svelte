<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4zbtcbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x4zbtcbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:person-bald" {...props}></Icon>
