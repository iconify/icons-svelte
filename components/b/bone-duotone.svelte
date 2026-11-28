<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9k11hbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9k11hbid primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bone-duotone" {...props}></Icon>
