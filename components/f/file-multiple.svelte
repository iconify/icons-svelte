<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4si1_bgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4si1_bgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:file-multiple" {...props}></Icon>
