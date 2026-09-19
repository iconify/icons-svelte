<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/i/i0wtp628f.css';
import '../../css/q/q7zvs2b6v.css';
import '../../css/d/d3tu5-t0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="i0wtp628f"/><circle class="q7zvs2b6v"/><path class="d3tu5-t0b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:motorbike-02" {...props}></Icon>
