<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0_6eubvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q0_6eubvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:knife" {...props}></Icon>
