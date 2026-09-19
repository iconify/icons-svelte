<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw0ouac-i.css';
import '../../css/g/g6gzcks7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="rw0ouac-i"/><path class="g6gzcks7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:globe-earth-alt" {...props}></Icon>
