<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/idjb8uvdc.css';
import '../../css/m/m8k6ofbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="idjb8uvdc"/><path clip-rule="evenodd" class="m8k6ofbaz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:arrow-cursor-click-2-flat" {...props}></Icon>
