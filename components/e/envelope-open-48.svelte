<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6va0ihvr.css';
import '../../css/y/y_9con1lw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r6va0ihvr"/><path class="y_9con1lw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:envelope-open-48" {...props}></Icon>
