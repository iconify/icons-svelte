<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_udarb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_udarb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cookie" {...props}></Icon>
