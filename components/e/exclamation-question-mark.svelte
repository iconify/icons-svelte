<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt-vn2f_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rt-vn2f_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:exclamation-question-mark" {...props}></Icon>
