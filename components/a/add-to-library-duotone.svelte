<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/ut4foe4in.css';
import '../../css/o/onkmdrc8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ut4foe4in"/><path class="onkmdrc8d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:add-to-library-duotone" {...props}></Icon>
