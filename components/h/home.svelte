<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo09p13bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wo09p13bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:home" {...props}></Icon>
