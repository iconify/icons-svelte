<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/g/g6o7mxbbp.css';
import '../../css/t/tlm8zbz-n.css';
import '../../css/l/ldn1gl3gg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g6o7mxbbp"/><path class="tlm8zbz-n"/><path class="ldn1gl3gg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:dices" {...props}></Icon>
