<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbigfv4ml.css';
import '../../css/z/zdyt6ubsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pbigfv4ml"/><path class="zdyt6ubsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:file-start" {...props}></Icon>
