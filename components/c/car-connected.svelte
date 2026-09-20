<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwmhcdcyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwmhcdcyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-connected" {...props}></Icon>
