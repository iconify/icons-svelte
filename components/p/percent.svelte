<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po_r04bta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="po_r04bta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:percent" {...props}></Icon>
