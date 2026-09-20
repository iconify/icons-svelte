<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ummc0db4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ummc0db4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alarm-arm-away-outline" {...props}></Icon>
