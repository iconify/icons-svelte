<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h-6grdhmq.css';
import '../../css/i/irl6mqbpf.css';
import '../../css/p/pgml1ac6f.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaVF51dhs"><g class="ft5dv1b6b"><path class="h-6grdhmq"/><path class="irl6mqbpf"/><path class="pgml1ac6f"/></g></mask></defs><path mask="url(#SVGaVF51dhs)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:hard-disk" {...props}></Icon>
