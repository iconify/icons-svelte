<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-px0kjof.css';
import '../../css/h/h_xc7ccwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-px0kjof"/><path class="h_xc7ccwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:power" {...props}></Icon>
