<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l9n4cmzlx.css';
import '../../css/v/voi9s6hpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l9n4cmzlx"/><path class="voi9s6hpy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:knob-duotone" {...props}></Icon>
