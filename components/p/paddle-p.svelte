<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifssrslal.css';
import '../../css/t/tdn_98ffj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifssrslal"/><path class="tdn_98ffj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:paddle-p" {...props}></Icon>
