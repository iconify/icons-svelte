<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/a/a9vsgkbga.css';
import '../../css/g/ghufp1bsu.css';
import '../../css/r/rr_rycfur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><circle class="a9vsgkbga"/><circle class="ghufp1bsu"/><path class="rr_rycfur"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:package-car" {...props}></Icon>
