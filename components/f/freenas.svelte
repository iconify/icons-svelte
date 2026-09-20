<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqgg7pbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqgg7pbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:freenas" {...props}></Icon>
