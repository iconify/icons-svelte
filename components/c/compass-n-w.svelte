<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi534ubzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="yi534ubzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:compass-n-w" {...props}></Icon>
