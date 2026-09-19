<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0z1eqbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0z1eqbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:notice-off" {...props}></Icon>
