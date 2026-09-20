<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqby38bfg.css';
import '../../css/u/uzk27_m6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqby38bfg"/><path class="uzk27_m6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:calculator-1" {...props}></Icon>
