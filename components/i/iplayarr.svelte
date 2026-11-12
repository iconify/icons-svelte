<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppubembly.css';
import '../../css/n/nlg65ubth.css';
import '../../css/d/dup3v4bcs.css';
import '../../css/v/vjapwvb6n.css';
import '../../css/j/j2p8_jaiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="ppubembly"/><path class="nlg65ubth"/><path class="dup3v4bcs"/><path class="vjapwvb6n"/><path class="j2p8_jaiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:iplayarr" {...props}></Icon>
