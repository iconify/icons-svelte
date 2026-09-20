<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn31dub8v.css';
import '../../css/c/ce504-bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="fn31dub8v"/><path class="ce504-bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:backblaze" {...props}></Icon>
