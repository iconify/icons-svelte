<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/d/dbp6o1bik.css';
import '../../css/y/yfrtf1_-w.css';
import '../../css/g/g26hojbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="dbp6o1bik"/><path class="yfrtf1_-w"/><path class="g26hojbfv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:battery-50" {...props}></Icon>
