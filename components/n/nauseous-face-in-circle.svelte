<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i70zh-6ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i70zh-6ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:nauseous-face-in-circle" {...props}></Icon>
