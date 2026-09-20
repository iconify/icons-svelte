<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iva73mbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iva73mbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:heart-slash-filled" {...props}></Icon>
