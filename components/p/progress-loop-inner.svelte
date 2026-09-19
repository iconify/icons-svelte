<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjc2o7b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hjc2o7b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:progress-loop-inner" {...props}></Icon>
