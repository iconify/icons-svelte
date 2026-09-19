<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf5pf_opx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lf5pf_opx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:next2" {...props}></Icon>
