<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el88tabhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="el88tabhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-nearby" {...props}></Icon>
