<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n280i_but.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n280i_but"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:diameter-variant" {...props}></Icon>
