<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/nw4n_tb5y.css';
import '../../css/j/jqmfhccyc.css';
import '../../css/n/no9almpsf.css';
import '../../css/h/hp3nybfqx.css';
import '../../css/u/udnigi2cc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="nw4n_tb5y"/><path class="jqmfhccyc"/><path class="no9almpsf"/><path class="hp3nybfqx"/><path class="udnigi2cc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:guitar" {...props}></Icon>
