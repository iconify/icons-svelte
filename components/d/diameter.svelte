<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_l8o78eb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_l8o78eb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:diameter" {...props}></Icon>
