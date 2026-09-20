<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkhjzob5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkhjzob5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:menorah" {...props}></Icon>
