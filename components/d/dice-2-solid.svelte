<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmzra2-rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmzra2-rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dice-2-solid" {...props}></Icon>
