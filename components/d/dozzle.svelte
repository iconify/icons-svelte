<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd25jv_3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xd25jv_3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dozzle" {...props}></Icon>
