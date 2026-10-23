<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne26k9bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ne26k9bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:beef" {...props}></Icon>
