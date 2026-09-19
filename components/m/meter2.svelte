<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjjnppbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kjjnppbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:meter2" {...props}></Icon>
