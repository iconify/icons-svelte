<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_3i9xybj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="j_3i9xybj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:minus-slash-plus" {...props}></Icon>
