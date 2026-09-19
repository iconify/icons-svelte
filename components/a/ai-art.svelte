<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/n/ncir--e1f.css';
import '../../css/q/q1zl0lc0k.css';
import '../../css/s/s7i40lndy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ncir--e1f"/><path class="q1zl0lc0k"/><path class="s7i40lndy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-art" {...props}></Icon>
