<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqd4dfbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqd4dfbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cylinder" {...props}></Icon>
