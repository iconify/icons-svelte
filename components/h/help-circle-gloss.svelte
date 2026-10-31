<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpbcez6dc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpbcez6dc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:help-circle-gloss" {...props}></Icon>
