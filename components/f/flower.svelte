<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwc5_gbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwc5_gbpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:flower" {...props}></Icon>
