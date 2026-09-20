<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g4zs08s-q.css';
import '../../css/t/tjaqipzba.css';
import '../../css/f/fo4ccr_rl.css';
import '../../css/z/zgpimybjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g4zs08s-q"/><path class="tjaqipzba"/><path class="fo4ccr_rl"/><path class="zgpimybjx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chart-pie" {...props}></Icon>
