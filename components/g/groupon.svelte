<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhp3rwbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhp3rwbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:groupon" {...props}></Icon>
