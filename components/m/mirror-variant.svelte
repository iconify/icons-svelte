<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbsqdclmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbsqdclmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mirror-variant" {...props}></Icon>
