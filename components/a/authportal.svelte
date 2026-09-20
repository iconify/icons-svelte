<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyt-wmt3x.css';
import '../../css/p/pmnep-p9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nyt-wmt3x"/><path class="pmnep-p9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:authportal" {...props}></Icon>
