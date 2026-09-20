<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miql4qbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="miql4qbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-file" {...props}></Icon>
