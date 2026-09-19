<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1tgt3btx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="e1tgt3btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:home" {...props}></Icon>
