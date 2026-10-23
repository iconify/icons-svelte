<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa9qyt-lj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fa9qyt-lj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:layer-arrow-up" {...props}></Icon>
