<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytx9e-bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytx9e-bxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:alarm-clock-off" {...props}></Icon>
