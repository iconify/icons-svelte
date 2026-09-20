<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d-0474bim.css';
import '../../css/o/odmn-us-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d-0474bim"/><path class="odmn-us-q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:lamp-duotone" {...props}></Icon>
