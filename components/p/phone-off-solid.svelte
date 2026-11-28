<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1dqgfbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1dqgfbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:phone-off-solid" {...props}></Icon>
