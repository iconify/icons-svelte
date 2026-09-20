<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw8u3l8sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yw8u3l8sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hydrogen-station" {...props}></Icon>
