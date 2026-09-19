<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/li-zi3elj.css';
import '../../css/b/bw511z_pe.css';
import '../../css/d/dfnr2jbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="li-zi3elj"/><path class="bw511z_pe"/><path class="dfnr2jbpz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:credit-card-not-accept" {...props}></Icon>
