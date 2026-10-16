<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzhw0_b9f.css';
import '../../css/q/qd81l2bmk.css';
import '../../css/l/lq2wswb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bzhw0_b9f"/><path class="qd81l2bmk"/><path class="lq2wswb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:emissions-trading-20" {...props}></Icon>
