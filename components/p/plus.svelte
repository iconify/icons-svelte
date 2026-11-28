<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6wz9sbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6wz9sbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:plus" {...props}></Icon>
