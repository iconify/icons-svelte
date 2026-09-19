<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx-u_nb3c.css';
import '../../css/j/j2velpbld.css';
import '../../css/c/ceojaobrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kx-u_nb3c"/><path class="j2velpbld"/><path class="ceojaobrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-today" {...props}></Icon>
