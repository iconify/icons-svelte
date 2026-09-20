<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vac2kxm0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vac2kxm0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:etsy" {...props}></Icon>
