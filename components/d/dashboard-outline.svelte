<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itcbor87g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="itcbor87g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:dashboard-outline" {...props}></Icon>
