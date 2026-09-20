<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuak7-9yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fuak7-9yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:deviantart" {...props}></Icon>
