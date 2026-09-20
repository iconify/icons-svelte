<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl-1-hbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl-1-hbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:insert-column-right" {...props}></Icon>
