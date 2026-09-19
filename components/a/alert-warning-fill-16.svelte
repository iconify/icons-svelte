<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgrlryu3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tgrlryu3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:alert-warning-fill-16" {...props}></Icon>
