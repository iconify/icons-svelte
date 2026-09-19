<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j307qjs0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="j307qjs0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:communications" {...props}></Icon>
