<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4bsj3b4y.css';
import '../../css/e/eoahs_b8g.css';
import '../../css/w/wbq43rb5g.css';
import '../../css/g/g7-s2nbhk.css';
import '../../css/l/l2w_hyait.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="q4bsj3b4y"/><path class="eoahs_b8g"/><path class="wbq43rb5g"/><path class="g7-s2nbhk"/><path class="l2w_hyait"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:guyana" {...props}></Icon>
