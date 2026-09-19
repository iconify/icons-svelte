<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg6y5jtyz.css';
import '../../css/j/jxx4uobjb.css';
import '../../css/z/z_q17jb9b.css';
import '../../css/z/zi2-bab_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mg6y5jtyz"/><path class="jxx4uobjb"/><path class="z_q17jb9b"/><path class="zi2-bab_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:hashes-filled" {...props}></Icon>
