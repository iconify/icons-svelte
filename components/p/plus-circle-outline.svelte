<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nucqz5bfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nucqz5bfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:plus-circle-outline" {...props}></Icon>
