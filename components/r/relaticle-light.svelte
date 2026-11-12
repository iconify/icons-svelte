<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc3xoabmc.css';
import '../../css/i/i9rrzu3ex.css';
import '../../css/n/n9pul1_5b.css';
import '../../css/z/z-uhu55bb.css';
import '../../css/d/dyso_pv8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fc3xoabmc"/><path class="i9rrzu3ex"/><path class="n9pul1_5b"/><path class="z-uhu55bb"/><path class="dyso_pv8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:relaticle-light" {...props}></Icon>
