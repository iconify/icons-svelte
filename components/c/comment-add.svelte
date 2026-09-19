<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk117eesu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="lk117eesu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:comment-add" {...props}></Icon>
