<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqa3tkb1n.css';
import '../../css/x/x_-bf3btl.css';
import '../../css/g/gm241tb0d.css';
import '../../css/i/icsy_rbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="sqa3tkb1n"><path class="x_-bf3btl"/><path class="gm241tb0d"/><path class="icsy_rbek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:calendar-plus-solid" {...props}></Icon>
