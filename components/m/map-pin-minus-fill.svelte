<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx29l3btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sx29l3btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-pin-minus-fill" {...props}></Icon>
