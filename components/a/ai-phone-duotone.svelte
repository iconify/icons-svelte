<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gb7_855gm.css';
import '../../css/x/x95x1mmua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gb7_855gm"/><path class="x95x1mmua"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-phone-duotone" {...props}></Icon>
