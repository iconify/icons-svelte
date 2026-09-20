<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jb-grt_jm.css';
import '../../css/o/o8joigbba.css';
import '../../css/o/o3uru2bok.css';
import '../../css/t/tt2xjccpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="jb-grt_jm"/><path class="o8joigbba"/><path class="o3uru2bok"/><path class="tt2xjccpu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:crypto-currency-bitcoin-chip" {...props}></Icon>
