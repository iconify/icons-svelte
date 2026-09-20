<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q18dlc9vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q18dlc9vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-imac-search" {...props}></Icon>
