<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nds_1k2vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nds_1k2vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-arrow-square-bold" {...props}></Icon>
