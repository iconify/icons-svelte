<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1bbw5cfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":619,"height":88};
const content = `<path class="i1bbw5cfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:five-guys" {...props}></Icon>
