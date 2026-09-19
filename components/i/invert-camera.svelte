<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/r/r-jxe9bpv.css';
import '../../css/o/omnpcg9gc.css';
import '../../css/z/zjbgnh96p.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgFAqpCEZ"><g class="v3_i3wktz"><path class="r-jxe9bpv"/><path class="omnpcg9gc"/><path class="zjbgnh96p"/></g></mask></defs><path mask="url(#SVGgFAqpCEZ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:invert-camera" {...props}></Icon>
