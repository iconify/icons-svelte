<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/r/rwog68bpz.css';
import '../../css/b/bymqqb55b.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG0J7ARb6P"><g class="v3_i3wktz"><path class="rwog68bpz"/><path class="bymqqb55b"/></g></mask></defs><path mask="url(#SVG0J7ARb6P)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:equalizer" {...props}></Icon>
