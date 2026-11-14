<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/v/vuutrabsm.css';
import '../../css/w/wnran_bnw.css';
import '../../css/y/yn5soub3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vuutrabsm"/><path class="wnran_bnw"/><path class="yn5soub3x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:collections-bookmark" {...props}></Icon>
