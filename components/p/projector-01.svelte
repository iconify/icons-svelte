<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/j8tqhzbcv.css';
import '../../css/t/t3h6qok3v.css';
import '../../css/s/s7eau4b8t.css';
import '../../css/h/hnhscoboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="j8tqhzbcv"/><circle class="t3h6qok3v"/><path class="s7eau4b8t"/><path class="hnhscoboi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:projector-01" {...props}></Icon>
