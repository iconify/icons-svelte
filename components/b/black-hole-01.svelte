<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/w/wi26wtigi.css';
import '../../css/g/gu4atmwpg.css';
import '../../css/b/b59eeib2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><ellipse class="wi26wtigi"/><path class="gu4atmwpg"/><path class="b59eeib2c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:black-hole-01" {...props}></Icon>
