<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p67fupb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="p67fupb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:hint-text" {...props}></Icon>
