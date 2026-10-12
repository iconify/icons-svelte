<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pb9hvpzxz.css';
import '../../css/l/l_wmtobsh.css';
import '../../css/u/u3pnkz42x.css';
import '../../css/c/c39ja90-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pb9hvpzxz"/><path class="l_wmtobsh"/><path class="u3pnkz42x"/><path class="c39ja90-l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cherry-duotone" {...props}></Icon>
