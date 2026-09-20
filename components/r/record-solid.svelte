<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snm_libuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snm_libuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:record-solid" {...props}></Icon>
