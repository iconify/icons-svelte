<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avtewbcvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avtewbcvp primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:corner-sharp-duotone" {...props}></Icon>
