<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nis2pu8ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nis2pu8ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-eye" {...props}></Icon>
