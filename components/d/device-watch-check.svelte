<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu23orbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu23orbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-watch-check" {...props}></Icon>
