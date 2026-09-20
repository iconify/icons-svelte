<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyi0vrbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyi0vrbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:graph-box" {...props}></Icon>
