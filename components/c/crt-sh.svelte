<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa-vdingl.css';
import '../../css/j/jm-ifbcih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qa-vdingl"/><path class="jm-ifbcih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crt-sh" {...props}></Icon>
