<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mii7rxkxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mii7rxkxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clock-6-round" {...props}></Icon>
