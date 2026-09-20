<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rob-vnojp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rob-vnojp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:data-transfer-circle-bold" {...props}></Icon>
