<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkdzwwbtq.css';
import '../../css/r/rzcvymb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="nkdzwwbtq"/><path class="rzcvymb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:librewolf" {...props}></Icon>
