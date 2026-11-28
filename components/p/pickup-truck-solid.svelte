<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib9qbhbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ib9qbhbju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pickup-truck-solid" {...props}></Icon>
