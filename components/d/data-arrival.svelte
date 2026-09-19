<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/f/fm8ultpfb.css';
import '../../css/y/ys21accyp.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGavg38Vjf"><g class="ufeehvblu"><path clip-rule="evenodd" class="fm8ultpfb"/><path class="ys21accyp"/></g></mask></defs><path mask="url(#SVGavg38Vjf)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:data-arrival" {...props}></Icon>
