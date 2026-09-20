<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tteo7nbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tteo7nbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:home-5-line" {...props}></Icon>
