<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5okodbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j5okodbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:column" {...props}></Icon>
