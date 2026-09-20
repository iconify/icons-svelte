<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx1_1khoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dx1_1khoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rewe" {...props}></Icon>
