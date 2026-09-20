<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shh_xvobj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shh_xvobj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:premier-league" {...props}></Icon>
