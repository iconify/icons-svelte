<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yosf0_bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yosf0_bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-walking-in-water" {...props}></Icon>
