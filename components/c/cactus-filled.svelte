<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n93ug4cnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n93ug4cnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cactus-filled" {...props}></Icon>
