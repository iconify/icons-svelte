<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c10rf7bkz.css';
import '../../css/e/em_yc89qg.css';
import '../../css/i/iyvdefbei.css';
import '../../css/b/by_69xb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c10rf7bkz"/><path class="em_yc89qg"/><path class="iyvdefbei"/><path class="by_69xb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lng-terminal-20-bold" {...props}></Icon>
