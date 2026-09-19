<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7uhcbces.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="x7uhcbces"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-han-filled" {...props}></Icon>
