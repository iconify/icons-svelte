<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_6i1t2sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="p_6i1t2sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:magnifying-glass" {...props}></Icon>
