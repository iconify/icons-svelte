<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i592gf__t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i592gf__t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:airplane-plus" {...props}></Icon>
