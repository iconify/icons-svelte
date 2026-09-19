<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/c/cc-uymnfm.css';
import '../../css/d/djg_lkhxc.css';
import '../../css/c/cvrj5xban.css';
import '../../css/w/wswjvjhxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="cc-uymnfm"/><ellipse class="djg_lkhxc"/><path class="cvrj5xban"/><path class="wswjvjhxc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:house-04" {...props}></Icon>
