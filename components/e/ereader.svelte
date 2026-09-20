<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp71m8bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tp71m8bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:ereader" {...props}></Icon>
