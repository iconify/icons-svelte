<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7fdm4bed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7fdm4bed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:light-bulb-on-filled" {...props}></Icon>
