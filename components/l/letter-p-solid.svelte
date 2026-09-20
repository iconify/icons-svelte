<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdpsiwb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdpsiwb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-p-solid" {...props}></Icon>
