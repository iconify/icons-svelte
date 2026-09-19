<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sn8w4jbap.css';
import '../../css/q/q_fvx4bhk.css';
import '../../css/w/wbd5s4b1z.css';
import '../../css/a/ab3lkccwf.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwt8adeDl"><g class="ft5dv1b6b"><rect class="sn8w4jbap"/><rect class="q_fvx4bhk"/><path class="wbd5s4b1z"/><path class="ab3lkccwf"/></g></mask></defs><path mask="url(#SVGwt8adeDl)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:perfume" {...props}></Icon>
