<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkvxsfbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkvxsfbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ironing-steam-off" {...props}></Icon>
