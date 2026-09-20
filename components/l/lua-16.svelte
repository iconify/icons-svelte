<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qudowwo1l.css';
import '../../css/r/rvdw2qbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qudowwo1l"/><path class="rvdw2qbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:lua-16" {...props}></Icon>
