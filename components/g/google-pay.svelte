<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d94nysxlv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d94nysxlv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-pay" {...props}></Icon>
