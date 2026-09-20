<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3js_p-8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3js_p-8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:google-docs" {...props}></Icon>
