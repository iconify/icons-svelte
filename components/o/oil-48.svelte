<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4lu07s0y.css';
import '../../css/l/l_8wx2fdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r4lu07s0y"/><path class="l_8wx2fdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:oil-48" {...props}></Icon>
