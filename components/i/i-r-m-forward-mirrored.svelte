<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8ni2pbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="d8ni2pbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:i-r-m-forward-mirrored" {...props}></Icon>
