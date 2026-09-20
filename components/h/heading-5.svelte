<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swmcjpbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swmcjpbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:heading-5" {...props}></Icon>
