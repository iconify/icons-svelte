<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf3e7424l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zf3e7424l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:more-vertical" {...props}></Icon>
