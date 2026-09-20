<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2-2zhbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2-2zhbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:home-2" {...props}></Icon>
