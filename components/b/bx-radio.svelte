<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr7ox659t.css';
import '../../css/k/kqxojurgk.css';
import '../../css/d/d5l_p05mg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gr7ox659t"/><circle class="kqxojurgk"/><path class="d5l_p05mg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-radio" {...props}></Icon>
