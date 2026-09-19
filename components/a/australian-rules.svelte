<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvgc23syg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="mvgc23syg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:australian-rules" {...props}></Icon>
