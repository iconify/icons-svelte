<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sde5eabln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="sde5eabln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:like-solid" {...props}></Icon>
