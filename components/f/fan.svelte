<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my0dy7qzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="my0dy7qzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fan" {...props}></Icon>
