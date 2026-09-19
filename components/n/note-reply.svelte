<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lry9t6b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="lry9t6b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:note-reply" {...props}></Icon>
