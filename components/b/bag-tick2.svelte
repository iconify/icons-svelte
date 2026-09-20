<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/g/g6y04tvey.css';
import '../../css/h/heknmubqx.css';
import '../../css/v/vyz1xubip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g6y04tvey"/><path class="heknmubqx"/><path class="vyz1xubip"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bag-tick2" {...props}></Icon>
