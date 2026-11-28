<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1xdfmb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1xdfmb_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:champagne-heart" {...props}></Icon>
