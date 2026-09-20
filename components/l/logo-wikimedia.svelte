<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpgnasd1n.css';
import '../../css/p/psgevsbih.css';
import '../../css/g/gs86xrbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xpgnasd1n"/><path class="psgevsbih"/><circle class="gs86xrbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:logo-wikimedia" {...props}></Icon>
