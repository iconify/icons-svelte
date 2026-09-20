<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gilks3ujm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gilks3ujm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-down-right-solid" {...props}></Icon>
