<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj5ibzbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aj5ibzbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:map-pin-check-gloss" {...props}></Icon>
