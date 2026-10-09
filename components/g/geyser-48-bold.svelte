<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6cvwtbsp.css';
import '../../css/e/eh_8zfvcn.css';
import '../../css/r/rmyb_66he.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d6cvwtbsp"/><path class="eh_8zfvcn"/><path class="rmyb_66he"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:geyser-48-bold" {...props}></Icon>
