<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/c/cnn4d64tb.css';
import '../../css/y/ynvxb_fkj.css';
import '../../css/m/mm331ob-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="cnn4d64tb"/><path class="ynvxb_fkj"/><path class="mm331ob-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pumpkin" {...props}></Icon>
