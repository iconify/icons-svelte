<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er91nobum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er91nobum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-watch-pause" {...props}></Icon>
