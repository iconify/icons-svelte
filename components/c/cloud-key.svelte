<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq2j6wvyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hq2j6wvyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-key" {...props}></Icon>
