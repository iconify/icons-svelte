<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tweod6bqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tweod6bqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:heart-pulse-solid" {...props}></Icon>
