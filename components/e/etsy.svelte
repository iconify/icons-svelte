<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctt6wubfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctt6wubfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:etsy" {...props}></Icon>
