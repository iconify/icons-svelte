<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn4lewb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xn4lewb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:development-containers" {...props}></Icon>
