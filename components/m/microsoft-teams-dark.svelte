<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdvc9woqc.css';
import '../../css/p/ptwpuid-h.css';
import '../../css/a/atnwqg8za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mdvc9woqc"/><path class="ptwpuid-h"/><path class="atnwqg8za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-teams-dark" {...props}></Icon>
