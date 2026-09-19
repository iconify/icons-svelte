<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoc1v7b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uoc1v7b7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:arrow-up-left2" {...props}></Icon>
