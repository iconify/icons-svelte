<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mewrqqw9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mewrqqw9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-cog" {...props}></Icon>
