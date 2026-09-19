<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd_rk-b_e.css';
import '../../css/g/ggn80i4hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hd_rk-b_e"/><path class="ggn80i4hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:link" {...props}></Icon>
