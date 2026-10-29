<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrlfh1-kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrlfh1-kd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:magnet" {...props}></Icon>
