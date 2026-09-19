<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4_pegsnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="q4_pegsnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:chevron-fold-10" {...props}></Icon>
