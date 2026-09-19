<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kje9bbc1f.css';
import '../../css/l/l5wvy5nfl.css';
import '../../css/b/b6ckcbcik.css';
import '../../css/l/lh9yiybsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="kje9bbc1f"/><path clip-rule="evenodd" class="l5wvy5nfl"/><path class="b6ckcbcik"/><path clip-rule="evenodd" class="lh9yiybsb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:child-cognition-outline" {...props}></Icon>
