<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ublp4abft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ublp4abft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-down-left" {...props}></Icon>
