<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6ad7xqxj.css';
import '../../css/p/p7e-r07_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q6ad7xqxj"/><path class="p7e-r07_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pfsense" {...props}></Icon>
