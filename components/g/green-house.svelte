<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv5q-h--d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gv5q-h--d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:green-house" {...props}></Icon>
