<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwqy98mpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwqy98mpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bottle-sharp" {...props}></Icon>
