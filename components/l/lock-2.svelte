<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0_p_sbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g0_p_sbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:lock-2" {...props}></Icon>
