<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pggcykugm.css';
import '../../css/s/sfbxtiqsz.css';
import '../../css/o/o8hoowu9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pggcykugm"/><path class="sfbxtiqsz"/><path class="o8hoowu9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:domainmod" {...props}></Icon>
