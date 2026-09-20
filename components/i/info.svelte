<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3u6-obdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q3u6-obdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:info" {...props}></Icon>
