<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxomwi7cb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pxomwi7cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:closed-caption" {...props}></Icon>
