<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s08sk7hat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s08sk7hat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:play" {...props}></Icon>
