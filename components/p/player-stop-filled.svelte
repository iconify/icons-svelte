<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_90ogbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_90ogbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:player-stop-filled" {...props}></Icon>
