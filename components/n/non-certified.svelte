<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwx_s704a.css';
import '../../css/q/qwe3y-4yj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zwx_s704a"/><path class="qwe3y-4yj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:non-certified" {...props}></Icon>
