<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvhw2-b0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jvhw2-b0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:page-checkedin" {...props}></Icon>
