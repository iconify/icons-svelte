<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdchihbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdchihbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cog-refresh-outline" {...props}></Icon>
