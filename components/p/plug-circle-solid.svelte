<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtbuivo0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtbuivo0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:plug-circle-solid" {...props}></Icon>
