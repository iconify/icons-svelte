<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oikujhwge.css';
import '../../css/m/madkpqytw.css';
import '../../css/u/u7i45u-pn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oikujhwge"/><path class="madkpqytw"/><path clip-rule="evenodd" class="u7i45u-pn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:radio-bold" {...props}></Icon>
