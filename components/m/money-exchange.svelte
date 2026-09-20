<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/e/ed3y3zbpp.css';
import '../../css/k/ktoaqbajk.css';
import '../../css/f/fcaoa701q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ed3y3zbpp"/><path class="ktoaqbajk"/><path class="fcaoa701q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:money-exchange" {...props}></Icon>
