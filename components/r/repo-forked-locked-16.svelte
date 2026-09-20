<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi067zb2o.css';
import '../../css/v/vrgmnk6vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mi067zb2o"/><path class="vrgmnk6vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:repo-forked-locked-16" {...props}></Icon>
