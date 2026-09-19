<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am917b6kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="am917b6kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:rain" {...props}></Icon>
