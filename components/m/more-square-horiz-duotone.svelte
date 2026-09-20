<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/auo6f96jh.css';
import '../../css/f/fn7hl3b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="auo6f96jh"/><path class="fn7hl3b8l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-square-horiz-duotone" {...props}></Icon>
