<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjhd4upqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hjhd4upqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:child" {...props}></Icon>
