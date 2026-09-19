<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/f/f1wfu4_qk.css';
import '../../css/y/y2m5b7byp.css';
import '../../css/k/krjghjbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="f1wfu4_qk"/><rect class="y2m5b7byp"/><path class="krjghjbfy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:milk-outline" {...props}></Icon>
