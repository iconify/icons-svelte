<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/abe4_nbce.css';
import '../../css/e/ecpcwmbmr.css';
import '../../css/l/la8qz22na.css';
import '../../css/r/rwwgm7bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="abe4_nbce"/><circle class="ecpcwmbmr"/><circle class="la8qz22na"/><path clip-rule="evenodd" class="rwwgm7bpd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:lol" {...props}></Icon>
