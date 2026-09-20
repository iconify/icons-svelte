<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr74ui3xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr74ui3xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:meta-alt" {...props}></Icon>
