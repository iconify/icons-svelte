<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvf6sthsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvf6sthsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chat-circle" {...props}></Icon>
