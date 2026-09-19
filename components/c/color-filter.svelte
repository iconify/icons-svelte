<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/w/wascf2ujt.css';
import '../../css/w/wee2qvrei.css';
import '../../css/t/timostb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wascf2ujt"/><path class="wee2qvrei"/><path class="timostb6x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:color-filter" {...props}></Icon>
