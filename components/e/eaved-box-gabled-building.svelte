<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms3-ehbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ms3-ehbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eaved-box-gabled-building" {...props}></Icon>
