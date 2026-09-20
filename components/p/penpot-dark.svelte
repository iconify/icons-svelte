<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwlceor8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":261.922,"height":345.941};
const content = `<path class="uwlceor8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:penpot-dark" {...props}></Icon>
