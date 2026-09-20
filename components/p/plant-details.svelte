<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn0sz_55w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="yn0sz_55w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:plant-details" {...props}></Icon>
