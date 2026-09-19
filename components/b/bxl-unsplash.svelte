<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gorjutbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gorjutbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-unsplash" {...props}></Icon>
