<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/c/cpeep6ycm.css';
import '../../css/q/qvra_uwad.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGKPxBxciR"><g class="hv130ab-t"><path clip-rule="evenodd" class="cpeep6ycm"/><path class="qvra_uwad"/></g></mask></defs><path mask="url(#SVGKPxBxciR)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:download-four" {...props}></Icon>
