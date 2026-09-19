<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/f_h_x_bua.css';
import '../../css/c/c9j4_hbrg.css';
import '../../css/p/p9l8-rlng.css';
import '../../css/z/zeggah3kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="f_h_x_bua"/><path class="c9j4_hbrg"/><path class="p9l8-rlng"/><path class="zeggah3kn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:no-smoking-circle" {...props}></Icon>
