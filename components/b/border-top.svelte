<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtkgymbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtkgymbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:border-top" {...props}></Icon>
