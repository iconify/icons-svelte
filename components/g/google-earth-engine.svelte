<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn1te-lst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gn1te-lst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-earth-engine" {...props}></Icon>
