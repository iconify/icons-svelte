<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg7j_bbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mg7j_bbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:indent-decrease-stroke-16" {...props}></Icon>
