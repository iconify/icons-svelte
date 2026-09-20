<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv6cbouia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fv6cbouia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-print" {...props}></Icon>
