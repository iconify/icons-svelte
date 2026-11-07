<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kr4evflrk.css';
import '../../css/j/jdzoki6fy.css';
import '../../css/s/s7et_6b9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kr4evflrk"/><path class="jdzoki6fy"/><path class="s7et_6b9q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dialog-line-duotone" {...props}></Icon>
