<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x36h_kb1w.css';
import '../../css/a/a8_rvkruz.css';
import '../../css/u/ufkix4bpb.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGjAI5eeMX"><g class="ft5dv1b6b"><path class="x36h_kb1w"/><path class="a8_rvkruz"/><path clip-rule="evenodd" class="ufkix4bpb"/></g></mask></defs><path mask="url(#SVGjAI5eeMX)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:browser-safari" {...props}></Icon>
