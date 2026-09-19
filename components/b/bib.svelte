<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/a/ajqn6mb9q.css';
import '../../css/u/uh2p8_idr.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPvZ9jdEH"><g class="ufeehvblu"><path class="ajqn6mb9q"/><path class="uh2p8_idr"/></g></mask></defs><path mask="url(#SVGPvZ9jdEH)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:bib" {...props}></Icon>
