<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oezb-5bow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":410,"height":82};
const content = `<path class="oezb-5bow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:amazon-music" {...props}></Icon>
