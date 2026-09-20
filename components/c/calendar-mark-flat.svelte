<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f49dq_byk.css';
import '../../css/f/fxw85nbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f49dq_byk"/><path clip-rule="evenodd" class="fxw85nbkl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:calendar-mark-flat" {...props}></Icon>
