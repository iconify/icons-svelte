<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibjkizgjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ibjkizgjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:parseable" {...props}></Icon>
