<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/o/o5dnc48bh.css';
import '../../css/v/v2xh89b7y.css';
import '../../css/c/c_63rybwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="o5dnc48bh"/><circle class="v2xh89b7y"/><circle class="c_63rybwj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chart-bubble-02" {...props}></Icon>
