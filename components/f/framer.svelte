<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk9s9zb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zk9s9zb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:framer" {...props}></Icon>
