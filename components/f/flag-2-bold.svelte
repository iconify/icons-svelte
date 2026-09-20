<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsxeq50_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsxeq50_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:flag-2-bold" {...props}></Icon>
