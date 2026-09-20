<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m800pbb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m800pbb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-tyre-alert" {...props}></Icon>
