<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzy6mq1xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzy6mq1xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:map-star" {...props}></Icon>
