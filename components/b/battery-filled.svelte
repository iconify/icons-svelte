<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xobw0_9rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xobw0_9rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:battery-filled" {...props}></Icon>
