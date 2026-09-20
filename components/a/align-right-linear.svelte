<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/s_gjrqbti.css';
import '../../css/q/qblnn4bzv.css';
import '../../css/j/j6ohuicfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s_gjrqbti"/><path class="qblnn4bzv"/><path class="j6ohuicfp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-right-linear" {...props}></Icon>
