<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r22q9yb_l.css';
import '../../css/f/fjrtewbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r22q9yb_l"/><path class="fjrtewbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reaparr-dark" {...props}></Icon>
