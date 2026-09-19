<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/w22_v0jqn.css';
import '../../css/l/lg_sgwbbl.css';
import '../../css/y/ym253vn8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="w22_v0jqn"/><path class="lg_sgwbbl"/><path class="ym253vn8u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:database" {...props}></Icon>
