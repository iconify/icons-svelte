<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkpuoo1nu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkpuoo1nu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:backpack-solid" {...props}></Icon>
