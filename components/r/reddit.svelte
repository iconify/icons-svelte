<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjh784b5x.css';
import '../../css/c/cx2ml4bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="hjh784b5x"/><path class="cx2ml4bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reddit" {...props}></Icon>
