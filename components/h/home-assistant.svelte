<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omh6_pbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omh6_pbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:home-assistant" {...props}></Icon>
