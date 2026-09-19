<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2wr4zbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="s2wr4zbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:column-options" {...props}></Icon>
