<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbzwv2bll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbzwv2bll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:linux-containers" {...props}></Icon>
