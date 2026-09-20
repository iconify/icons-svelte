<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fao72i.css';
import '../../css/q/qa-o7h.css';
import '../../css/i/i5u07d.css';
import '../../css/y/ydovum.css';
import '../../css/z/z24blz.css';
import '../../css/p/pun1do.css';
import '../../css/s/so-from-66.css';
import '../../css/s/so-to-0.css';
import '../../css/f/fade-to-1.css';
import '../../css/f/fill-to-1.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fao72i qa-o7h"/><path class="i5u07d qa-o7h"/><circle class="ydovum z24blz"/><path class="pun1do ydovum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:image-filled" {...props}></Icon>
