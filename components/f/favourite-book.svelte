<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/a-pi4vqeb.css';
import '../../css/e/eciy7-bwj.css';
import '../../css/e/e3xegxdul.css';
import '../../css/k/kd2q2mdzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="a-pi4vqeb"/><path class="eciy7-bwj"/><path class="e3xegxdul"/><path class="kd2q2mdzv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:favourite-book" {...props}></Icon>
