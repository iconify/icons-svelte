<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/o/oxiiz1bbk.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhVhB8bpf"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="oxiiz1bbk"/></g></mask></defs><path mask="url(#SVGhVhB8bpf)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:circle-left-down" {...props}></Icon>
