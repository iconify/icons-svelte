<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2m65bbab.css';
import '../../css/g/gcpnklyer.css';
import '../../css/k/kqncv3w7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f2m65bbab"/><path class="gcpnklyer"/><path class="kqncv3w7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-incoming-20" {...props}></Icon>
