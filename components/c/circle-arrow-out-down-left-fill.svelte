<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m39rcgbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m39rcgbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-arrow-out-down-left-fill" {...props}></Icon>
