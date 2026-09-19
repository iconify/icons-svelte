<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mver5acni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mver5acni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:memo" {...props}></Icon>
