<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/wwim7wbwn.css';
import '../../css/e/eay7wabqi.css';
import '../../css/x/xj1eo1kcv.css';
import '../../css/s/snk52kbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="wwim7wbwn"/><path class="eay7wabqi"/><path class="xj1eo1kcv"/><path class="snk52kbzr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pizza-02" {...props}></Icon>
