<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwe37rb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwe37rb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:goblet-2-line" {...props}></Icon>
