<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug-axbtvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ug-axbtvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:calm-1-filled" {...props}></Icon>
