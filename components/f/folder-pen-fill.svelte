<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m46l96acm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m46l96acm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-pen-fill" {...props}></Icon>
