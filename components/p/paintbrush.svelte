<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/nc-2l0j_u.css';
import '../../css/b/bah0qkb9c.css';
import '../../css/h/h_f_e5fyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="nc-2l0j_u"/><path class="bah0qkb9c"/><path class="h_f_e5fyu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:paintbrush" {...props}></Icon>
