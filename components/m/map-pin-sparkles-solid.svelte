<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abydlvrjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abydlvrjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:map-pin-sparkles-solid" {...props}></Icon>
