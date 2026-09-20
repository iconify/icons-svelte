<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-zt9rbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-zt9rbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cloud-download" {...props}></Icon>
