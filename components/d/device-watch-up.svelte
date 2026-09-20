<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbm9b0bbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbm9b0bbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-watch-up" {...props}></Icon>
