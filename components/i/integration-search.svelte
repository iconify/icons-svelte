<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnu9x_btz.css';
import '../../css/k/koyp8_atq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qnu9x_btz"/><path class="koyp8_atq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:integration-search" {...props}></Icon>
