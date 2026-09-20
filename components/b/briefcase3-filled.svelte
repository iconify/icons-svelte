<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/plru9gbxl.css';
import '../../css/o/o74pufqtt.css';
import '../../css/t/t8xme76ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="plru9gbxl"/><path class="o74pufqtt"/><path class="t8xme76ku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:briefcase3-filled" {...props}></Icon>
