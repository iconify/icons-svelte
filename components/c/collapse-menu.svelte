<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu899ws8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="cu899ws8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:collapse-menu" {...props}></Icon>
