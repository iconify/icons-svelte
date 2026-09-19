<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvbdow_er.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lvbdow_er"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:minus" {...props}></Icon>
