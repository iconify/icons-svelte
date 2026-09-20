<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6l7bxb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6l7bxb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:diving-flippers" {...props}></Icon>
