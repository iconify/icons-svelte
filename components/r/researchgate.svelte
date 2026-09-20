<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mat8ltbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mat8ltbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:researchgate" {...props}></Icon>
