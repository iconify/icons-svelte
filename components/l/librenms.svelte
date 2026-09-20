<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wivhkqb-l.css';
import '../../css/m/m7vfhemuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wivhkqb-l"/><path class="m7vfhemuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:librenms" {...props}></Icon>
