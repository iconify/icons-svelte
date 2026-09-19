<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvk_bnbme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xvk_bnbme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:flowchart" {...props}></Icon>
