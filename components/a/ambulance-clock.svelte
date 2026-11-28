<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvifft_3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvifft_3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:ambulance-clock" {...props}></Icon>
