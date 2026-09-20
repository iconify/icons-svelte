<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv8qo5c_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv8qo5c_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:passport-remove" {...props}></Icon>
