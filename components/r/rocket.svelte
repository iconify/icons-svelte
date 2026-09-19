<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1_setxkq.css';
import '../../css/b/bu8lizbbx.css';
import '../../css/l/l9ibikb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g1_setxkq"/><path class="bu8lizbbx"/><path class="l9ibikb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:rocket" {...props}></Icon>
