<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbt97mb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbt97mb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hotel-bed-line" {...props}></Icon>
