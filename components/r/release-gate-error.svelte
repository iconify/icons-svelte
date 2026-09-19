<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dok0cd5zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dok0cd5zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:release-gate-error" {...props}></Icon>
