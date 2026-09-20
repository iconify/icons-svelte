<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aamwa-sar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aamwa-sar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:antenna-bars-5" {...props}></Icon>
