<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw5agubmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw5agubmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ionos" {...props}></Icon>
