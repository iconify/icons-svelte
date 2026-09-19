<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4ly-lb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4ly-lb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:book" {...props}></Icon>
