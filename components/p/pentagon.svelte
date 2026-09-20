<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5gbfqb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5gbfqb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pentagon" {...props}></Icon>
