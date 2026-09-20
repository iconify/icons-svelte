<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkktpcc1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkktpcc1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:radio-2-fill" {...props}></Icon>
