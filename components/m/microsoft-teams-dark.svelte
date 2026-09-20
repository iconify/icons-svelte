<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggt1geb1l.css';
import '../../css/x/xr2facclf.css';
import '../../css/a/atnwqg8za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ggt1geb1l"/><path class="xr2facclf"/><path class="atnwqg8za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-teams-dark" {...props}></Icon>
