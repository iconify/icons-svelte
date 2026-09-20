<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgkseabvl.css';
import '../../css/w/w702a-b9z.css';
import '../../css/f/f2c_ymbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fgkseabvl"/><path class="w702a-b9z"/><path class="f2c_ymbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cloudflare" {...props}></Icon>
