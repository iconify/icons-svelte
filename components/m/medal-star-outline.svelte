<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt4dle_us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vt4dle_us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-star-outline" {...props}></Icon>
