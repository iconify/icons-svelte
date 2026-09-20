<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peoz5pb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="peoz5pb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:airplane-edit" {...props}></Icon>
