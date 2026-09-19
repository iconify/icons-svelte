<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etkmd655w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="etkmd655w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:chess-king" {...props}></Icon>
