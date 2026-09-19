<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkaj5omtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkaj5omtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:gatsby-js" {...props}></Icon>
