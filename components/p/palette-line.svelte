<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysa-polzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ysa-polzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:palette-line" {...props}></Icon>
