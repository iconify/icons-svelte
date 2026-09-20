<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/din7kacmm.css';
import '../../css/o/ojbfnibyv.css';
import '../../css/j/jjw_gzn8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="din7kacmm"/><path class="ojbfnibyv"/><path class="jjw_gzn8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-contacts-dark" {...props}></Icon>
