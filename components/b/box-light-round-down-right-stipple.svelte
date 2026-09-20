<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz63_s8wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="wz63_s8wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-round-down-right-stipple" {...props}></Icon>
