<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvhew3bau.css';
import '../../css/t/tb-x70blq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jvhew3bau"/><path class="tb-x70blq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ai-launch" {...props}></Icon>
