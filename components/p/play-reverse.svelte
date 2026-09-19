<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti6j9ubny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ti6j9ubny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:play-reverse" {...props}></Icon>
