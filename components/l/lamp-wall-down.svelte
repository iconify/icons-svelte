<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds8lrw-bm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds8lrw-bm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:lamp-wall-down" {...props}></Icon>
