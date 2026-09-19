<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2tv6bbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2tv6bbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-waterleak" {...props}></Icon>
