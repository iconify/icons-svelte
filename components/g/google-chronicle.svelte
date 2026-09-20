<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxgpxloro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxgpxloro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-chronicle" {...props}></Icon>
