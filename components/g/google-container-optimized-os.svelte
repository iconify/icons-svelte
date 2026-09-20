<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gss19nbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gss19nbzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-container-optimized-os" {...props}></Icon>
