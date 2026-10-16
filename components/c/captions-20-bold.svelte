<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6dd8jb9u.css';
import '../../css/o/oaiisxbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l6dd8jb9u"/><path class="oaiisxbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:captions-20-bold" {...props}></Icon>
