<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nisud3b2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nisud3b2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:deepgram" {...props}></Icon>
