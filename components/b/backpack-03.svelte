<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/g0pj_sagf.css';
import '../../css/h/hl9_4mpqh.css';
import '../../css/x/xr8gsh1az.css';
import '../../css/i/iqu_9x4pn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="g0pj_sagf"/><path class="hl9_4mpqh"/><path class="xr8gsh1az"/><path class="iqu_9x4pn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:backpack-03" {...props}></Icon>
