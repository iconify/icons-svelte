<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/warsr81xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="warsr81xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hockey-puck" {...props}></Icon>
