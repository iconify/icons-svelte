<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moj52yb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="moj52yb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ars-technica" {...props}></Icon>
