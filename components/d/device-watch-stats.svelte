<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc5iqbbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nc5iqbbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-watch-stats" {...props}></Icon>
