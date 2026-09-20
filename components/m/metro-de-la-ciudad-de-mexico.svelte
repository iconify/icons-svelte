<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6cbsebpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6cbsebpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:metro-de-la-ciudad-de-mexico" {...props}></Icon>
