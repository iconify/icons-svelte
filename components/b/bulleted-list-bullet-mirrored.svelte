<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6rfu7b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="c6rfu7b7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:bulleted-list-bullet-mirrored" {...props}></Icon>
