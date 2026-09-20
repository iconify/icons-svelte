<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v96n9tbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v96n9tbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-vr" {...props}></Icon>
