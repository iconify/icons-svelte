<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xod5pz_vt.css';
import '../../css/g/gdwzp4r6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xod5pz_vt"/><path class="gdwzp4r6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:backuppc-light" {...props}></Icon>
