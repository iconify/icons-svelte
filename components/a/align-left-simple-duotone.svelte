<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lw1vs2beq.css';
import '../../css/d/dainh5byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lw1vs2beq"/><path class="dainh5byp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-left-simple-duotone" {...props}></Icon>
