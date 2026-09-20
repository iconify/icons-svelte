<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq5p5vhri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vq5p5vhri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:indifferent-circle-solid" {...props}></Icon>
