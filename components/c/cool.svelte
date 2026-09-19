<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trjilpbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="trjilpbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:cool" {...props}></Icon>
