<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcbt0na6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcbt0na6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:applause" {...props}></Icon>
