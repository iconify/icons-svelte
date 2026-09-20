<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gd89r1hxn.css';
import '../../css/i/i0e-9r7nn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gd89r1hxn"/><path clip-rule="evenodd" class="i0e-9r7nn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:cyborg-flat" {...props}></Icon>
