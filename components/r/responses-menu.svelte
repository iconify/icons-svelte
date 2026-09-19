<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d16z8nbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="d16z8nbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:responses-menu" {...props}></Icon>
