<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n40rqhhah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n40rqhhah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:bars-3-center-left" {...props}></Icon>
