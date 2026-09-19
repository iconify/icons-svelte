<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a4i2bbc8w.css';
import '../../css/p/pv7xol74s.css';
import '../../css/z/z9youcaqg.css';
import '../../css/v/v0m5xdb6q.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<mask id="ipSProportionalScaling0"><g class="ft5dv1b6b"><g clip-path="url(#ipSProportionalScaling1)" class="a4i2bbc8w"><path class="pv7xol74s"/><path class="z9youcaqg"/></g><defs><clipPath id="ipSProportionalScaling1"><path class="v0m5xdb6q"/></clipPath></defs></g></mask><path mask="url(#ipSProportionalScaling0)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:proportional-scaling" {...props}></Icon>
