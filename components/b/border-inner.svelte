<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xiaqwfbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xiaqwfbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:border-inner" {...props}></Icon>
