<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz8g2ghyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vz8g2ghyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:brain-outline" {...props}></Icon>
