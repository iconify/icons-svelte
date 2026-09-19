<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp_dy82bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jp_dy82bb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:face-pending-filled" {...props}></Icon>
