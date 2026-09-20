<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfn6x6blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfn6x6blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-n-solid" {...props}></Icon>
