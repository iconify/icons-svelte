<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-e0brbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-e0brbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:beehive-off-outline" {...props}></Icon>
