<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9ccybcno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z9ccybcno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:pc-display-horizontal" {...props}></Icon>
