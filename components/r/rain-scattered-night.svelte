<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm_kd6_tw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lm_kd6_tw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rain-scattered-night" {...props}></Icon>
