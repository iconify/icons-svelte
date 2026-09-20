<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3kclgbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3kclgbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-earth" {...props}></Icon>
