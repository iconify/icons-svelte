<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2omcpm6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="d2omcpm6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:branch-fork-2" {...props}></Icon>
