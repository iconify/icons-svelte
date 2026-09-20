<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-z2yuw-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-z2yuw-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-clock" {...props}></Icon>
