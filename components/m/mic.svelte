<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmets6kjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cmets6kjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:mic" {...props}></Icon>
