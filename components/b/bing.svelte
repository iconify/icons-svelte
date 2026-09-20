<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyp0zek2m.css';
import '../../css/e/eicf32biw.css';
import '../../css/h/hjuyob91s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jyp0zek2m"/><path class="eicf32biw"/><path class="hjuyob91s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bing" {...props}></Icon>
