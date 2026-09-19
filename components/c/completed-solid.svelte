<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1z05y-nr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w1z05y-nr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:completed-solid" {...props}></Icon>
