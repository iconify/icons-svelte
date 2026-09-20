<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv16s7lvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yv16s7lvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:candy-round-1" {...props}></Icon>
