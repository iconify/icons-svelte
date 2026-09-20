<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j09di39bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j09di39bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:car-line" {...props}></Icon>
