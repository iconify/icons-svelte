<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at5p92bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="at5p92bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:location-error-filled" {...props}></Icon>
