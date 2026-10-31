<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvoi15yhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvoi15yhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-arrow-down-fill-round" {...props}></Icon>
