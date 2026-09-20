<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqc0fgbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqc0fgbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:droplet-dollar" {...props}></Icon>
