<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9df3ow_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9df3ow_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:allergen-off-outline" {...props}></Icon>
