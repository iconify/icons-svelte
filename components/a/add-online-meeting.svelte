<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abrj3cc4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="abrj3cc4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:add-online-meeting" {...props}></Icon>
