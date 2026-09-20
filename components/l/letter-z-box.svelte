<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6unzo74d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6unzo74d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-z-box" {...props}></Icon>
