<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsucddc_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zsucddc_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:google-plus" {...props}></Icon>
