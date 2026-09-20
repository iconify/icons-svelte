<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc7erx8nu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc7erx8nu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:one-octagon-solid" {...props}></Icon>
