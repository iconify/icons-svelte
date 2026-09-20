<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu2ir04zv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu2ir04zv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-minus" {...props}></Icon>
