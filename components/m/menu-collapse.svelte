<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugg_ysbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugg_ysbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:menu-collapse" {...props}></Icon>
