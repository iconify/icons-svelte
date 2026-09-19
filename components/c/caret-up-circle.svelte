<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws4hu2e0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ws4hu2e0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:caret-up-circle" {...props}></Icon>
