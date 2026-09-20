<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quim4nbfq.css';
import '../../css/t/tlxfihr8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="quim4nbfq"/><path class="tlxfihr8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netonnet" {...props}></Icon>
