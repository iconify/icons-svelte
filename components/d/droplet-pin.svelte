<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdg6c3btx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdg6c3btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:droplet-pin" {...props}></Icon>
