<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yaqgv4bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yaqgv4bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:droplet-x" {...props}></Icon>
