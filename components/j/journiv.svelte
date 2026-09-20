<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feh17ircu.css';
import '../../css/v/vbxcdz47q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="feh17ircu"/><path class="vbxcdz47q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:journiv" {...props}></Icon>
