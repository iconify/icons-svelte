<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbj_drvej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbj_drvej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:camera" {...props}></Icon>
