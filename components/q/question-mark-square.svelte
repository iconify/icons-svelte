<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/i/ina_babpj.css';
import '../../css/k/k1vkz0b3o.css';
import '../../css/z/z7h9dmbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="ina_babpj"/><path class="k1vkz0b3o"/><rect class="z7h9dmbpz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:question-mark-square" {...props}></Icon>
