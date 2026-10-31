<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sch1fb_tq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sch1fb_tq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:letter-f" {...props}></Icon>
