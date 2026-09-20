<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bspjx2xhr.css';
import '../../css/x/xje7wbbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bspjx2xhr"/><path class="xje7wbbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:amex" {...props}></Icon>
