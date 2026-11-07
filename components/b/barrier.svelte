<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wul2d8-4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wul2d8-4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:barrier" {...props}></Icon>
