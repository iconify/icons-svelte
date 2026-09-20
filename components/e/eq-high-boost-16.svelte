<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh9jl8b2r.css';
import '../../css/g/gis6lfbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qh9jl8b2r"/><path class="gis6lfbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:eq-high-boost-16" {...props}></Icon>
