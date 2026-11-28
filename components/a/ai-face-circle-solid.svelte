<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm_voxbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jm_voxbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-face-circle-solid" {...props}></Icon>
