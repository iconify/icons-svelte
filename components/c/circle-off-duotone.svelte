<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la0tybdob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="la0tybdob primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-off-duotone" {...props}></Icon>
