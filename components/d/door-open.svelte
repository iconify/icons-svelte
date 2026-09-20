<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt-3sbkfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mt-3sbkfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:door-open" {...props}></Icon>
