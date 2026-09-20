<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dle73-aae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dle73-aae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:quantcast" {...props}></Icon>
