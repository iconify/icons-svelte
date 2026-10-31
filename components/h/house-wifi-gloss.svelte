<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyxast55d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyxast55d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:house-wifi-gloss" {...props}></Icon>
