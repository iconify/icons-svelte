<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt7c_7kbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lt7c_7kbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bluetooth-x" {...props}></Icon>
