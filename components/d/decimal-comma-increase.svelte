<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbnx1ps0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbnx1ps0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:decimal-comma-increase" {...props}></Icon>
