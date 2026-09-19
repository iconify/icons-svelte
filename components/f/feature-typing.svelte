<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5gbubc_q.css';
import '../../css/q/ql7ybibdx.css';
import '../../css/v/vfr8jsk1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="m5gbubc_q"/><circle class="ql7ybibdx"/><path class="vfr8jsk1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:feature-typing" {...props}></Icon>
