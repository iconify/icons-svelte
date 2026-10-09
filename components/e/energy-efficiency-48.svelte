<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9f9bgb4v.css';
import '../../css/r/rtxnsrb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w9f9bgb4v"/><path class="rtxnsrb6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-efficiency-48" {...props}></Icon>
