<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvn7yqk5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lvn7yqk5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:basketball" {...props}></Icon>
