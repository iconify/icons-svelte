<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re3_sbpib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="re3_sbpib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:camera-solid" {...props}></Icon>
