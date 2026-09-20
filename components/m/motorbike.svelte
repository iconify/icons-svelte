<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxg4r3bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxg4r3bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:motorbike" {...props}></Icon>
