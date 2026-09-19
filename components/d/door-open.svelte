<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx-x6g2ze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx-x6g2ze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:door-open" {...props}></Icon>
