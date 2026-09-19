<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhoje1s1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lhoje1s1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:arrow-up" {...props}></Icon>
