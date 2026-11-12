<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvrfp6bae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvrfp6bae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-flame" {...props}></Icon>
