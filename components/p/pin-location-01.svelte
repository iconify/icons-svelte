<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/tcwe4ewrv.css';
import '../../css/c/cy50z2-cm.css';
import '../../css/e/e-zqnqb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="tcwe4ewrv"/><path class="cy50z2-cm"/><path class="e-zqnqb2e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pin-location-01" {...props}></Icon>
