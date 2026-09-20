<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/c/c7zkydbij.css';
import '../../css/c/ct9fr6bou.css';
import '../../css/s/shz66wb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c7zkydbij"/><path class="ct9fr6bou"/><path class="shz66wb0b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:megaphone-a" {...props}></Icon>
