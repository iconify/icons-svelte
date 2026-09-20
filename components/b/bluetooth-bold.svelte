<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syjcuql6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="syjcuql6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bluetooth-bold" {...props}></Icon>
