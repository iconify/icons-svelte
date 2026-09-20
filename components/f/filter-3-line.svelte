<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pffl33b1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pffl33b1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:filter-3-line" {...props}></Icon>
