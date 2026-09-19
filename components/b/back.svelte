<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9s-fzwsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="d9s-fzwsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:back" {...props}></Icon>
