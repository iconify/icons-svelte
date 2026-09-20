<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pjaa9acpi.css';
import '../../css/r/rf3su1b-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pjaa9acpi"/><path clip-rule="evenodd" class="rf3su1b-m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:hand-held-tablet-drawing-flat" {...props}></Icon>
