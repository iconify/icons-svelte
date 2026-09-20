<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w08-fwv8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w08-fwv8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cloud-moon-rain" {...props}></Icon>
