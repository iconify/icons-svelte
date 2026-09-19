<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/f/f6rrh3byv.css';
import '../../css/q/qfiyzsrnv.css';
import '../../css/v/vhiyc9brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f6rrh3byv"/><path class="qfiyzsrnv"/><path class="vhiyc9brz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:mutation-2" {...props}></Icon>
