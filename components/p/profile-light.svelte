<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/nj1tek_eb.css';
import '../../css/z/z2o0ujiuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="nj1tek_eb"/><circle class="z2o0ujiuj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:profile-light" {...props}></Icon>
