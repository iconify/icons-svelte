<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/eedy2_2_u.css';
import '../../css/j/jyg2dbbxi.css';
import '../../css/d/d69r_jv7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="eedy2_2_u"/><path class="jyg2dbbxi"/><path class="d69r_jv7v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:club" {...props}></Icon>
