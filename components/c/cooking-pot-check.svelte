<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osd5_vbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osd5_vbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cooking-pot-check" {...props}></Icon>
