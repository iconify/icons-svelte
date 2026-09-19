<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai8h5-bdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ai8h5-bdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:return-key" {...props}></Icon>
