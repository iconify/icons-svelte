<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1os19l5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b1os19l5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:kiss-mark" {...props}></Icon>
