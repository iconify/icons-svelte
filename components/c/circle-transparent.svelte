<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbp5xr6qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbp5xr6qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:circle-transparent" {...props}></Icon>
