<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsl08fp4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsl08fp4r primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:curtains-open-duotone" {...props}></Icon>
