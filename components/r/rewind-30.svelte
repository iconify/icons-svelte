<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrndicbcc.css';
import '../../css/y/ydysvhh_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mrndicbcc"/><path class="ydysvhh_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rewind-30" {...props}></Icon>
