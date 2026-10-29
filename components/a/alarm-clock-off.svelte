<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w24qb0b6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w24qb0b6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:alarm-clock-off" {...props}></Icon>
