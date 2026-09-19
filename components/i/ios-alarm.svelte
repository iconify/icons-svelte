<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmi-16b0h.css';
import '../../css/l/l544h_tbr.css';
import '../../css/l/l-m2k2bsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mmi-16b0h"/><path class="l544h_tbr"/><g><path class="l-m2k2bsw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-alarm" {...props}></Icon>
