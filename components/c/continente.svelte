<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuytl7iwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iuytl7iwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:continente" {...props}></Icon>
